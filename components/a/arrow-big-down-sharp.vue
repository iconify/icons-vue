<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_c0albfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_c0albfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-big-down-sharp" /></template>
