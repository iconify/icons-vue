<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1_chib4c.css';
import '../../css/u/uw_598fhe.css';
import '../../css/k/k6d-cvqep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u1_chib4c"/><path class="uw_598fhe"/><path class="k6d-cvqep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-x-20" /></template>
