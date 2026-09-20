<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuak7-9yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuak7-9yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deviantart" /></template>
