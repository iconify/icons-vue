<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x27z5vb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x27z5vb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-variant" /></template>
