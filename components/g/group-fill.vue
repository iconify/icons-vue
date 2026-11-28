<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6boo9b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c6boo9b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:group-fill" /></template>
