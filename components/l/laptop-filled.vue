<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzo0z4img.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzo0z4img"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:laptop-filled" /></template>
