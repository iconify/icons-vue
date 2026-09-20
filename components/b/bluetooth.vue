<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vobx5xbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vobx5xbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bluetooth" /></template>
