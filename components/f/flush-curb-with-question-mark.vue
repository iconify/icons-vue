<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz4ck4-4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rz4ck4-4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flush-curb-with-question-mark" /></template>
