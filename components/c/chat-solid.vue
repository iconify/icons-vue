<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsz22fr3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bsz22fr3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:chat-solid" /></template>
