<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgc4r4n1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vgc4r4n1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-right-quote-fill" /></template>
