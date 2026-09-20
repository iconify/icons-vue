<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7m83e-jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="e7m83e-jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-favorite-star-reward-rating-rate-social-star-media-favorite-like-stars" /></template>
