<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj2-0-jta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj2-0-jta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:film-play" /></template>
