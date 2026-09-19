<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu6i2gb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tu6i2gb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-pp" /></template>
