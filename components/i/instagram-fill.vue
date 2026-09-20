<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys5kuk1gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys5kuk1gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:instagram-fill" /></template>
