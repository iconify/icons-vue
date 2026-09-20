<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-la4bbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":4605.7,"height":2723.6};
const content = `<path class="n-la4bbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amazon-prime" /></template>
