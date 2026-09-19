<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg_5oxbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dg_5oxbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-right-heart-fill" /></template>
