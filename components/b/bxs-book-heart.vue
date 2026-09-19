<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkp8b6b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkp8b6b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-book-heart" /></template>
