<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2qe06bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u2qe06bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:add-chat-two-outline" /></template>
