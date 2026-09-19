<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9y-sxz8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c9y-sxz8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-square" /></template>
