<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dth_nabga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dth_nabga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:greater-than-equal" /></template>
