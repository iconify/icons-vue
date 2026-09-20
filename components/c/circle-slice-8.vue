<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaji_jb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaji_jb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-slice-8" /></template>
