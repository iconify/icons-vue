<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4_t9jggu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4_t9jggu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fullscreen-square-filled" /></template>
