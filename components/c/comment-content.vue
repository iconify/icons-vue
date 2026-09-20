<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3y2lb35h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="i3y2lb35h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:comment-content" /></template>
