<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcx77dbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcx77dbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:langchain-corporate" /></template>
