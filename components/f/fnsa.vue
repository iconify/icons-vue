<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe0w18bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe0w18bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fnsa" /></template>
