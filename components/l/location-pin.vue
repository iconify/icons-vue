<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9ncz__nf.css';
import '../../css/u/u-c3y7bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h9ncz__nf"/><path class="u-c3y7bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:location-pin" /></template>
