<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1m5k6buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1m5k6buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:linux-solid" /></template>
