<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc-b-cbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-b-cbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-up" /></template>
