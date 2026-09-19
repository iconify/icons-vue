<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq2dc2dvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sq2dc2dvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:ball-and-socket-joint" /></template>
