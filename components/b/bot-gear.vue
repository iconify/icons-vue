<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxlqh4btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxlqh4btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bot-gear" /></template>
