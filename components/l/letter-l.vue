<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gli4g3-ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gli4g3-ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-l" /></template>
