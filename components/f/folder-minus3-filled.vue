<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z77c00bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z77c00bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-minus3-filled" /></template>
