<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoj03-bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zoj03-bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-award-half-star-reward-rating-rate-social-star-media-favorite-like-stars-half" /></template>
