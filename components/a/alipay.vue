<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7l9lfbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y7l9lfbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:alipay" /></template>
