<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umi_2wm3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umi_2wm3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-locked-fill" /></template>
