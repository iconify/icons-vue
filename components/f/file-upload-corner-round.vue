<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch3n8pvnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch3n8pvnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-upload-corner-round" /></template>
