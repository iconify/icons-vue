<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtm8-702u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtm8-702u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:audio" /></template>
