<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzytkr3yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nzytkr3yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cmake" /></template>
