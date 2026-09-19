<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iktdgbbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":888,"height":1000};
const content = `<path class="iktdgbbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-sleep" /></template>
