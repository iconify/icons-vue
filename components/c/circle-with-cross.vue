<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5l_tybju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t5l_tybju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:circle-with-cross" /></template>
