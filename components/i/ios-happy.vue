<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f34p5dbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f34p5dbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-happy" /></template>
