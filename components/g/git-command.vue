<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgd5zucvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgd5zucvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:git-command" /></template>
