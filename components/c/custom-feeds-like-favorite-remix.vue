<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdou84mty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vdou84mty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:custom-feeds-like-favorite-remix" /></template>
