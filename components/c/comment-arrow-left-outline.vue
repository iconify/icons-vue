<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8b5eihmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8b5eihmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-arrow-left-outline" /></template>
