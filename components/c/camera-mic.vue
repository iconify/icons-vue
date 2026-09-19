<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-z7z2qao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="a-z7z2qao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera-mic" /></template>
