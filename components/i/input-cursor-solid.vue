<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjjo1ibry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjjo1ibry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:input-cursor-solid" /></template>
