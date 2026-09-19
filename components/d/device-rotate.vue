<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsk9mvbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nsk9mvbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:device-rotate" /></template>
