<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy9r3v0qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy9r3v0qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-gloss" /></template>
