<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsjznyj_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsjznyj_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:123-20" /></template>
