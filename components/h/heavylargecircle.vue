<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3cy-l8ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3cy-l8ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heavylargecircle" /></template>
