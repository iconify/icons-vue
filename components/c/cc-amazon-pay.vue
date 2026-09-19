<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg9anbbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bg9anbbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cc-amazon-pay" /></template>
