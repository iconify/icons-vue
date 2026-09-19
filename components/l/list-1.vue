<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rktrmjtat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="rktrmjtat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:list-1" /></template>
