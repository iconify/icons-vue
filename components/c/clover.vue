<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5oyh1b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q5oyh1b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:clover" /></template>
