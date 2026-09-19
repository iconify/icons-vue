<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urgz1kfox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urgz1kfox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:dribbble" /></template>
