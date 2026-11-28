<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m47zqrbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m47zqrbmi primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-right-duotone" /></template>
