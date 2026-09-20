<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-z9jebeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t-z9jebeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:left-bracket-and-cube" /></template>
