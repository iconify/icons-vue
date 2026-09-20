<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn0o6fb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn0o6fb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:linkedin-2-solid" /></template>
