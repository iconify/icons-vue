<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1i-h0bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1i-h0bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chess" /></template>
