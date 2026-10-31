<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inhk1yb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inhk1yb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-fill-round" /></template>
