<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfcs2q2pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hfcs2q2pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-square-heart-fill" /></template>
