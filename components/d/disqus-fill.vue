<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgzjx28fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgzjx28fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:disqus-fill" /></template>
