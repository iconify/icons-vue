<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j34d9k6ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j34d9k6ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-heart-filled" /></template>
