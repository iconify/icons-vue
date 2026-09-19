<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6a4tubxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r6a4tubxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-right-text-fill" /></template>
