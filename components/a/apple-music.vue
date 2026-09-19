<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di7sjtb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di7sjtb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:apple-music" /></template>
