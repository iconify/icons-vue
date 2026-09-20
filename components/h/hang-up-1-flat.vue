<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hikmf2byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hikmf2byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:hang-up-1-flat" /></template>
