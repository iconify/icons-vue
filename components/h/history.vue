<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl36l_yds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fl36l_yds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:history" /></template>
