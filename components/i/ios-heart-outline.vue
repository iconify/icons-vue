<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd9f0ccnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hd9f0ccnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-heart-outline" /></template>
