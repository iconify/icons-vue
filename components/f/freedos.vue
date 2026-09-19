<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw36togob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vw36togob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:freedos" /></template>
