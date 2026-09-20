<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1e-couig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1e-couig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmarks-fill" /></template>
