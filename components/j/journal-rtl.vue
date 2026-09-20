<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukr-_lbgh.css';
import '../../css/y/yqzq-hios.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ukr-_lbgh"/><path class="yqzq-hios"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:journal-rtl" /></template>
