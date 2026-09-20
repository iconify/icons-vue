<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj7wg2bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yj7wg2bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instagram-reels-dark" /></template>
