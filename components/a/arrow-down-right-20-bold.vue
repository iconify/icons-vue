<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ans_9vb2b.css';
import '../../css/x/x-_i1mkli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ans_9vb2b"/><path class="x-_i1mkli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-right-20-bold" /></template>
