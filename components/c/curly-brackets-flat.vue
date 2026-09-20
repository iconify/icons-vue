<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m88e10b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m88e10b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:curly-brackets-flat" /></template>
