<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csip7ekyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":512};
const content = `<path class="csip7ekyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cpcdosc" /></template>
