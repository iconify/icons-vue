<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu-9-sbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yu-9-sbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:calculator" /></template>
