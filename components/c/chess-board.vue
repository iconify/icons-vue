<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj6hiybni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cj6hiybni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chess-board" /></template>
