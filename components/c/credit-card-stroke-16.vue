<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qst2e4_nj.css';
import '../../css/w/w7a4y5boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="qst2e4_nj"/><path class="w7a4y5boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:credit-card-stroke-16" /></template>
