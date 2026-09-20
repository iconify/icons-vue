<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odvxrfbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odvxrfbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:dashboard-circle-flat" /></template>
