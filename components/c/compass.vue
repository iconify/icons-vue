<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufgy1p4li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ufgy1p4li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:compass" /></template>
