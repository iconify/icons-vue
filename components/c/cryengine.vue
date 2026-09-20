<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orb9p3cfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orb9p3cfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cryengine" /></template>
