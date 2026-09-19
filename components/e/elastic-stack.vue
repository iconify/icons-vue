<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw54uz_0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kw54uz_0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:elastic-stack" /></template>
