<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjqvlpb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjqvlpb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-sitemap" /></template>
