<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z25e2cb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z25e2cb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:garage-lock" /></template>
