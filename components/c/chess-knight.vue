<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4qanbbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4qanbbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:chess-knight" /></template>
