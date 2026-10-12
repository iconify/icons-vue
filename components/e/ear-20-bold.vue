<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1xrsabpz.css';
import '../../css/u/ug018k_ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t1xrsabpz"/><path class="ug018k_ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ear-20-bold" /></template>
