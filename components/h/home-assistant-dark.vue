<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njsbplffl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="njsbplffl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:home-assistant-dark" /></template>
