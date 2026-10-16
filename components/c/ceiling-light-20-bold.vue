<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo_phgozt.css';
import '../../css/c/c7-acjc4q.css';
import '../../css/n/n2-k-0btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fo_phgozt"/><path class="c7-acjc4q"/><path class="n2-k-0btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ceiling-light-20-bold" /></template>
