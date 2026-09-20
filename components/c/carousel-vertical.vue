<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jps5fp-dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jps5fp-dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:carousel-vertical" /></template>
