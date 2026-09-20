<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5v7bsbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="z5v7bsbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:handle" /></template>
