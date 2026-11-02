<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7ma1pbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7ma1pbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmarks-fill" /></template>
