<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffl-jwtyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffl-jwtyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lorry" /></template>
