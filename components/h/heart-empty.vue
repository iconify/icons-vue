<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m16sctqau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m16sctqau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:heart-empty" /></template>
