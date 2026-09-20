<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq_u29btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hq_u29btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:electrical-lightning-arrestor-and-bolt" /></template>
