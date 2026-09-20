<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv-robcde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tv-robcde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gear-filled" /></template>
