<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inma3mwja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="inma3mwja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ansible" /></template>
