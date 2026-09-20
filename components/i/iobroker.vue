<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia0poz8wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia0poz8wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:iobroker" /></template>
