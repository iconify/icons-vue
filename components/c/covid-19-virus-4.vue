<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6tp-6btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6tp-6btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid-19-virus-4" /></template>
