<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whrj7cfjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whrj7cfjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instagram-reels-light" /></template>
