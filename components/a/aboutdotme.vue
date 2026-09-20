<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot1z51b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot1z51b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aboutdotme" /></template>
