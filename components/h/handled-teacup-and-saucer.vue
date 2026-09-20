<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6-iqpklj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w6-iqpklj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:handled-teacup-and-saucer" /></template>
