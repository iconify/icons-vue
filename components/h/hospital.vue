<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q39pzgo6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q39pzgo6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hospital" /></template>
