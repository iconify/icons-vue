<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2smo5btm.css';
import '../../css/k/k52gxob7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h2smo5btm"/><path class="k52gxob7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-stamp" /></template>
