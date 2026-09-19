<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaxzipbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaxzipbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-moon-rain" /></template>
