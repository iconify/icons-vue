<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-0ytcb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t-0ytcb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:colorado" /></template>
