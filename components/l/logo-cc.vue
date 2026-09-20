<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpqjhyevn.css';
import '../../css/i/i5eb24tdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zpqjhyevn"/><path class="i5eb24tdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-cc" /></template>
