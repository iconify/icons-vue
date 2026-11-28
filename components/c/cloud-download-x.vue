<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn9dj_esb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn9dj_esb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-download-x" /></template>
