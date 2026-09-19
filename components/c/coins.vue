<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be780fp0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="be780fp0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:coins" /></template>
