<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wys_fmb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wys_fmb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:coursera" /></template>
