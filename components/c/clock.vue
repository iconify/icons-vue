<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9ldgvhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kd9ldgvhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:clock" /></template>
