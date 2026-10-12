<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlwaf4b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xlwaf4b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-list-fill-20" /></template>
