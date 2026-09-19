<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vij84ybpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vij84ybpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:attachment-thin" /></template>
