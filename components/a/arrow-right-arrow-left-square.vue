<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs9dc65rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rs9dc65rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right-arrow-left-square" /></template>
