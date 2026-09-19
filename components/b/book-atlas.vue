<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcp0p3h6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pcp0p3h6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:book-atlas" /></template>
