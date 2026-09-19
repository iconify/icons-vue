<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvwknurtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvwknurtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-no-entry" /></template>
