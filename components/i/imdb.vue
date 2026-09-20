<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clu8t7j1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="clu8t7j1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:imdb" /></template>
