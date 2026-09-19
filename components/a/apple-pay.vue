<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb1ht8aoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tb1ht8aoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:apple-pay" /></template>
