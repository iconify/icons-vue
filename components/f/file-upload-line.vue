<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy0zzymhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy0zzymhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-upload-line" /></template>
