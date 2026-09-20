<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebz0dxbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebz0dxbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connector-hex-filled" /></template>
