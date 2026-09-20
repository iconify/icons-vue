<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdjbrmb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdjbrmb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:airplay-audio" /></template>
