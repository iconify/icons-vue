<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cukg2h6lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cukg2h6lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:five-plus" /></template>
