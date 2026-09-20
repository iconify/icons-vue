<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esa6e0o2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="esa6e0o2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-logo-windows-2-os-system-microsoft" /></template>
