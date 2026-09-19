<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rob-th-6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rob-th-6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:loop" /></template>
