<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llhn36wnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llhn36wnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aeroflot" /></template>
