<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxvgxxkwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bxvgxxkwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:2-plus-above-water" /></template>
