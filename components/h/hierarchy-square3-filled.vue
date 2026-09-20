<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/genxdrb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="genxdrb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hierarchy-square3-filled" /></template>
