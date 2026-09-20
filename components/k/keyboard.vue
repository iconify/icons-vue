<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysuj-ynse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ysuj-ynse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:keyboard" /></template>
