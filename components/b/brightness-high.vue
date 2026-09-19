<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxijxzs2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":496};
const content = `<path class="uxijxzs2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-high" /></template>
