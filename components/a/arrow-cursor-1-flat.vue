<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyvkscb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyvkscb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:arrow-cursor-1-flat" /></template>
