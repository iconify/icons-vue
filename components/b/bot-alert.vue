<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waeyn_hha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waeyn_hha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bot-alert" /></template>
