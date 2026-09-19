<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko0dg5bwi.css';
import '../../css/d/d70zu1-xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ko0dg5bwi"/><path class="d70zu1-xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cut-sharp" /></template>
