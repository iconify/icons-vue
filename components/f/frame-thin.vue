<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtai_3fli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtai_3fli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:frame-thin" /></template>
