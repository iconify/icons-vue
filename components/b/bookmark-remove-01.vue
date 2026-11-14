<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu6vqt9py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu6vqt9py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-remove-01" /></template>
