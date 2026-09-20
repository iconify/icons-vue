<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn6nhnk7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mn6nhnk7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-infinite-loop" /></template>
