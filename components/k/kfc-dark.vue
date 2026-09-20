<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd6a86fya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":150,"height":111};
const content = `<path class="jd6a86fya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kfc-dark" /></template>
