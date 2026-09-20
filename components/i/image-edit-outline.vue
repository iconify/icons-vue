<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7_4cvbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7_4cvbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-edit-outline" /></template>
