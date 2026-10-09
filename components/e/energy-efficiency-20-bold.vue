<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sut7r2bvd.css';
import '../../css/o/oebaf-blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sut7r2bvd"/><path class="oebaf-blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-efficiency-20-bold" /></template>
