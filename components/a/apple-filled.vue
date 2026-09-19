<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd0ko1baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd0ko1baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:apple-filled" /></template>
