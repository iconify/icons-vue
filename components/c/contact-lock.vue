<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcfd24bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcfd24bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contact-lock" /></template>
