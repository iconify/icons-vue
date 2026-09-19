<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhapq6b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhapq6b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:comment-detail" /></template>
