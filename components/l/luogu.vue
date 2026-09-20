<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eva_pbbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eva_pbbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:luogu" /></template>
