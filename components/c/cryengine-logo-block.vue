<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpu-0gzml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpu-0gzml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:cryengine-logo-block" /></template>
