<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2dfsxb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r2dfsxb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:alipay" /></template>
