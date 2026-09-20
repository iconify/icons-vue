<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myapyabmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="myapyabmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:drink-food-fruit" /></template>
