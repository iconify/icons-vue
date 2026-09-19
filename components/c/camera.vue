<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbj_drvej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbj_drvej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:camera" /></template>
