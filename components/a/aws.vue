<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu1nrd9jh.css';
import '../../css/g/g9iec9jch.css';
import '../../css/i/i7vrkybqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="vu1nrd9jh"><path class="g9iec9jch"/><path class="i7vrkybqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aws" /></template>
