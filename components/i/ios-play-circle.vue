<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je97gj2zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="je97gj2zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-play-circle" /></template>
