<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbmst969n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pbmst969n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-square-dots-fill" /></template>
