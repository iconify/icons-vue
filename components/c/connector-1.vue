<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udcsjnntu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udcsjnntu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:connector-1" /></template>
