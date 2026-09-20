<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2nv7g9ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2nv7g9ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-outline" /></template>
