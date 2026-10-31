<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci9iid05n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci9iid05n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-sparkle-fill-round" /></template>
