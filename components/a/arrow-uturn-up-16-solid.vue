<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl9l6sb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rl9l6sb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-up-16-solid" /></template>
