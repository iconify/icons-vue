<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f66lmuynv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f66lmuynv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-signal-solid" /></template>
