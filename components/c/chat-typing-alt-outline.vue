<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw9fzjpvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bw9fzjpvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chat-typing-alt-outline" /></template>
