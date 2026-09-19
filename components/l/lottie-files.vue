<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw7ii9h6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw7ii9h6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:lottie-files" /></template>
