<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir8b8ublh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir8b8ublh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bell-ring" /></template>
