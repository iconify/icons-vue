<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4i-yacpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4i-yacpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:film-fill" /></template>
