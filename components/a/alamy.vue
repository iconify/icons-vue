<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em64t9lzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em64t9lzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alamy" /></template>
