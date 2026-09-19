<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqd_e4bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="iqd_e4bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-justify-stroke-12" /></template>
