<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5zmk_xeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z5zmk_xeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:heart" /></template>
