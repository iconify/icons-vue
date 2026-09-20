<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s--_y-b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s--_y-b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-check-outline" /></template>
