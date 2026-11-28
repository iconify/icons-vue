<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8wk18mvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8wk18mvc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-duotone" /></template>
