<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmz_29bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmz_29bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:between-vertical-start-line" /></template>
