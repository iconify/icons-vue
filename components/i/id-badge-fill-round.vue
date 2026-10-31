<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwxn38blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwxn38blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-badge-fill-round" /></template>
