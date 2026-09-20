<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peq-q4buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="peq-q4buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:drink-food-cookie" /></template>
