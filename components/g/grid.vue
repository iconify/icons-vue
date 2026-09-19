<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks5a3nbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ks5a3nbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:grid" /></template>
