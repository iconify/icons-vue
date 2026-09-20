<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bno8x-bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bno8x-bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:building-solid" /></template>
