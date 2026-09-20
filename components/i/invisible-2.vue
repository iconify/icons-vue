<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh554tb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh554tb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:invisible-2" /></template>
