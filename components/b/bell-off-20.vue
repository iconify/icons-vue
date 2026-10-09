<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7lbhgb_q.css';
import '../../css/i/iffp3wblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u7lbhgb_q"/><path class="iffp3wblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-off-20" /></template>
