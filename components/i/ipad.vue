<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wldwkeb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wldwkeb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:ipad" /></template>
