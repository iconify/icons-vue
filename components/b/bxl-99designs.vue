<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6m7-ac3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6m7-ac3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-99designs" /></template>
