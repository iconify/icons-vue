<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_6gorsfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_6gorsfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:add-pdf" /></template>
