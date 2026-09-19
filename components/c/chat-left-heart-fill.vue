<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl3hfwebj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xl3hfwebj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-left-heart-fill" /></template>
