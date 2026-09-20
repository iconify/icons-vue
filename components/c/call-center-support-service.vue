<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw5mlobsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uw5mlobsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:call-center-support-service" /></template>
