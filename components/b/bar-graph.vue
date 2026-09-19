<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnwq-4lnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wnwq-4lnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:bar-graph" /></template>
