<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxj4jgb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kxj4jgb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:amazon-pay" /></template>
