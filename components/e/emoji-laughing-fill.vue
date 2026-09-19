<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re2vbxbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="re2vbxbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-laughing-fill" /></template>
