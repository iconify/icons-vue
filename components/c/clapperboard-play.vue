<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4wx-tw7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4wx-tw7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clapperboard-play" /></template>
