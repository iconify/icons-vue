<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_v0yebin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j_v0yebin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:connector-stroke-20" /></template>
