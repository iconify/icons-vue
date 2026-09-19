<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya7p8kszo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya7p8kszo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lit-house-number" /></template>
