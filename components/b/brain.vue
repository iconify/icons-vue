<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf2kmilea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mf2kmilea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:brain" /></template>
