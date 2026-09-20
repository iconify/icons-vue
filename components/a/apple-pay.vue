<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd9e1pbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pd9e1pbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:apple-pay" /></template>
