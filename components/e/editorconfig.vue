<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tthmh2ddu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tthmh2ddu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:editorconfig" /></template>
