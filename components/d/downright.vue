<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chy3nfbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="chy3nfbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:downright" /></template>
