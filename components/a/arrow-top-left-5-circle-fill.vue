<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6gpl0b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6gpl0b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-5-circle-fill" /></template>
