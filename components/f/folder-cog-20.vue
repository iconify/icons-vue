<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3me-4caq.css';
import '../../css/w/wgtq23b2b.css';
import '../../css/i/i9p3igbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c3me-4caq"/><path class="wgtq23b2b"/><path class="i9p3igbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-cog-20" /></template>
