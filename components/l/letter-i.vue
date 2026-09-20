<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh9mc2bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh9mc2bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-i" /></template>
