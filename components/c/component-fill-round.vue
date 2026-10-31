<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fph4z6l2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fph4z6l2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-fill-round" /></template>
