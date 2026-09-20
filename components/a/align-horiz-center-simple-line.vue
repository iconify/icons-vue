<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq8bjuytw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq8bjuytw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-horiz-center-simple-line" /></template>
