<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh3o5mjqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh3o5mjqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:anthropic-light" /></template>
