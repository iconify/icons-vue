<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwzc0c7sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="uwzc0c7sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-style" /></template>
