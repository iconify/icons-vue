<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwa43fbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwa43fbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:key" /></template>
