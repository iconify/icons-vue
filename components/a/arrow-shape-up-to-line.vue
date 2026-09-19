<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nycn5mb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nycn5mb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-up-to-line" /></template>
