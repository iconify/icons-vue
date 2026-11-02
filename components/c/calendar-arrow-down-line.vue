<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw7442-qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw7442-qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-arrow-down-line" /></template>
