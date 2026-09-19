<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5dc-7bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s5dc-7bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cc-apple-pay" /></template>
