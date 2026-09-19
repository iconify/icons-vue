<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr4mn3_sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kr4mn3_sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-heart" /></template>
