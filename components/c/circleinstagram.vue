<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg-l0fbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pg-l0fbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleinstagram" /></template>
