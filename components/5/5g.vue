<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km9-o-bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km9-o-bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:5g" /></template>
