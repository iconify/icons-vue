<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itw962baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itw962baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:craft-cms" /></template>
