<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp3ta-1pq.css';
import '../../css/g/gfpj9w7rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp3ta-1pq"/><path class="gfpj9w7rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:like-chat-bold" /></template>
