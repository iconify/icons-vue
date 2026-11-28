<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d65dfhbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d65dfhbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-upload" /></template>
