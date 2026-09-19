<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlyt_4bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlyt_4bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:blood-drop-filled" /></template>
