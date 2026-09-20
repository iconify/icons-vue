<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4r97vg-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4r97vg-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:infinity-sharp" /></template>
