<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duliw2bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":644};
const content = `<path class="duliw2bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:alignleft" /></template>
