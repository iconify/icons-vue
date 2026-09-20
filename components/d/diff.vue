<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy9o_fwfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vy9o_fwfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:diff" /></template>
