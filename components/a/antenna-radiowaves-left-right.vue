<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcxdhb84c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lcxdhb84c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:antenna-radiowaves-left-right" /></template>
