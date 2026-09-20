<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzes-1bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nzes-1bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:call-center-support-service-solid" /></template>
