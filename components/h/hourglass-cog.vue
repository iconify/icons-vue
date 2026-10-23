<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-ik06-dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-ik06-dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hourglass-cog" /></template>
