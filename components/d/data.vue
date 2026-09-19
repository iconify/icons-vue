<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgowae9de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vgowae9de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:data" /></template>
