<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dalqx4w3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dalqx4w3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:boat" /></template>
