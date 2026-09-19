<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydvq6bbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydvq6bbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bookmark-heart" /></template>
