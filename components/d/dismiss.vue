<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hszbwt4ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hszbwt4ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:dismiss" /></template>
