<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4t4632zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4t4632zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:buy-n-large" /></template>
