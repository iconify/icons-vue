<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf59xfbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf59xfbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lamp-outline" /></template>
