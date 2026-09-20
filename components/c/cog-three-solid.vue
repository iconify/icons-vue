<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pngpyibfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pngpyibfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cog-three-solid" /></template>
