<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd_-mkbbv.css';
import '../../css/d/dmbrnfbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd_-mkbbv"/><path clip-rule="evenodd" class="dmbrnfbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-close-outline" /></template>
