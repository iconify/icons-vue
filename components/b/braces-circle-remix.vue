<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw74qgbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bw74qgbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:braces-circle-remix" /></template>
