<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yavjvdbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yavjvdbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:basket-outline" /></template>
