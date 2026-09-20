<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk8e_lbql.css';
import '../../css/k/kkpkbbccb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk8e_lbql"/><path class="kkpkbbccb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:haze-line" /></template>
