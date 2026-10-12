<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_9hn1bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t_9hn1bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bookmark-stroke-20" /></template>
