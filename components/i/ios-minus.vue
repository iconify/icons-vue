<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg4qjdbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yg4qjdbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-minus" /></template>
