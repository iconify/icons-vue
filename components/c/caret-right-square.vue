<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcppewgpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcppewgpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-right-square" /></template>
