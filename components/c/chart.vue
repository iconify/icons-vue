<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqmlo2b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lqmlo2b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:chart" /></template>
