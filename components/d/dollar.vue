<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moux05b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":24};
const content = `<path class="moux05b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:dollar" /></template>
