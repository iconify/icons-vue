<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0wv7wb3z.css';
import '../../css/e/epk77cclf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p0wv7wb3z"/><path class="epk77cclf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:a-frame-48" /></template>
