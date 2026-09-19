<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tday29biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tday29biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:call" /></template>
