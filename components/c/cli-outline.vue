<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw7inrb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tw7inrb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cli-outline" /></template>
