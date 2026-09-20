<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-x_denun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-x_denun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cloth-1" /></template>
