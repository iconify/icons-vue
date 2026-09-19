<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_y22ybks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="j_y22ybks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:finance" /></template>
