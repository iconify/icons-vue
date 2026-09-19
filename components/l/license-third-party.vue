<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiwjo4boz.css';
import '../../css/d/dt0zo1djr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kiwjo4boz"/><path class="dt0zo1djr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:license-third-party" /></template>
