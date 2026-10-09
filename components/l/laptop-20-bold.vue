<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okxwzshqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="okxwzshqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laptop-20-bold" /></template>
