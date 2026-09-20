<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i70y1sbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i70y1sbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:igdb" /></template>
