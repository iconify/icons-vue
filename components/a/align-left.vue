<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voxnpu-mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voxnpu-mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:align-left" /></template>
