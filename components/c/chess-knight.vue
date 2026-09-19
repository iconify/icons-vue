<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsttf0l7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wsttf0l7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chess-knight" /></template>
