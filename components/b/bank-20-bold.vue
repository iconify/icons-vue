<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrqzf1bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lrqzf1bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bank-20-bold" /></template>
