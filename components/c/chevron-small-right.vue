<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohawap6hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ohawap6hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-small-right" /></template>
