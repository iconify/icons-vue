<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmu7ij10d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmu7ij10d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-more-line" /></template>
