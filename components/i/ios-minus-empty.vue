<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqy-2vh-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sqy-2vh-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-minus-empty" /></template>
