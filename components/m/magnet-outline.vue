<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u37-xachj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u37-xachj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-outline" /></template>
