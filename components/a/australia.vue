<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyw3y3bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wyw3y3bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:australia" /></template>
