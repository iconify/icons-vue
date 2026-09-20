<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4ac1nk3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ac1nk3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-off" /></template>
