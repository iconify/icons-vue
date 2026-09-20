<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8z41mb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8z41mb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bmw" /></template>
