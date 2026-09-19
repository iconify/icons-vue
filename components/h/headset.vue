<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1hudx9od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1hudx9od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:headset" /></template>
