<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wppvwobie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wppvwobie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-king" /></template>
