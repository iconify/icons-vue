<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayz2avbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayz2avbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gsap" /></template>
