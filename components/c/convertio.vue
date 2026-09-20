<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tef6ddacq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tef6ddacq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:convertio" /></template>
