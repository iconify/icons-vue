<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfgv5d9ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfgv5d9ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:camera-solid" /></template>
