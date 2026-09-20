<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm5v2qbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tm5v2qbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hand-held-tablet-drawing-solid" /></template>
