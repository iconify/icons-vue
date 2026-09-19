<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p43etnbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p43etnbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-right-fill" /></template>
