<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cup618odg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cup618odg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:chevron-left" /></template>
