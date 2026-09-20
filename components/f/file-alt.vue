<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umw_9vdvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umw_9vdvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:file-alt" /></template>
