<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h66rubb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="h66rubb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hangout" /></template>
