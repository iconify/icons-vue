<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me3btxa7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me3btxa7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:box-open" /></template>
