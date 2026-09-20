<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbc9jmbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbc9jmbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-play-outline" /></template>
