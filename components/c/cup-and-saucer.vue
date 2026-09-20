<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epjnci0vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="epjnci0vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cup-and-saucer" /></template>
