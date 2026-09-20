<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1c1n3btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1c1n3btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codeceptjs" /></template>
