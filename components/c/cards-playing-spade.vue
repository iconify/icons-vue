<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9jpwwt3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9jpwwt3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-spade" /></template>
