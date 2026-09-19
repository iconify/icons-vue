<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ethcq8boj.css';
import '../../css/s/sit0_i-ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ethcq8boj"/><path class="sit0_i-ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-add" /></template>
