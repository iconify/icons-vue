<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iypbzcy7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iypbzcy7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:input-cursor-move" /></template>
