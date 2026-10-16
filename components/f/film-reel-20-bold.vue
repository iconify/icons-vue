<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8xo_c6fy.css';
import '../../css/k/kwq58xm-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g8xo_c6fy"/><path class="kwq58xm-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:film-reel-20-bold" /></template>
