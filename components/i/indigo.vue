<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtqd48bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtqd48bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:indigo" /></template>
