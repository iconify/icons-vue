<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/v/vw30x_0wh.css';
import '../../css/w/wpfh7ntzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="vw30x_0wh"/><path class="wpfh7ntzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-storybook" /></template>
