<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnz67-bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cnz67-bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:basketball-stroke-20" /></template>
