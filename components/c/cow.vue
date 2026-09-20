<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzup_wbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wzup_wbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cow" /></template>
