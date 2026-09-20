<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6u543atc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6u543atc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:list-expressive" /></template>
