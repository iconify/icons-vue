<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqa97dmfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqa97dmfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bell-off" /></template>
