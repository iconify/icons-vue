<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_a9fclgc.css';
import '../../css/b/blj5kcbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":150};
const content = `<path class="l_a9fclgc"/><path class="blj5kcbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:android" /></template>
