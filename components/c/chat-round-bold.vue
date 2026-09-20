<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsaue0b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsaue0b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-bold" /></template>
