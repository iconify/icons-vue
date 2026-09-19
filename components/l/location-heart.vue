<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjvt0lfrb.css';
import '../../css/n/nu2_-nbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hjvt0lfrb"/><path class="nu2_-nbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-heart" /></template>
