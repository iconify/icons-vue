<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcoa8gbfx.css';
import '../../css/c/cnkm8cblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcoa8gbfx"/><path class="cnkm8cblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:baseball" /></template>
