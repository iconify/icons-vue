<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssgbogglr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssgbogglr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:instagram-line" /></template>
