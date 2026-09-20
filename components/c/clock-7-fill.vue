<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je37nc8jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="je37nc8jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-7-fill" /></template>
