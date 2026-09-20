<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r32gc8bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r32gc8bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-text-left-outline" /></template>
