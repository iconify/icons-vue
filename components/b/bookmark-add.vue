<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt6q9oj5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt6q9oj5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-add" /></template>
