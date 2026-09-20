<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtr5qkmsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtr5qkmsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gandi" /></template>
