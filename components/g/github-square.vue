<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el39ovbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="el39ovbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:github-square" /></template>
