<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaj3ch19q.css';
import '../../css/l/lj_w3s1cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iaj3ch19q"/><path class="lj_w3s1cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:badge" /></template>
