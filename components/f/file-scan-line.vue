<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-3y3_nir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-3y3_nir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-scan-line" /></template>
