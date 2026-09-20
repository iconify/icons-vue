<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8rkp0bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u8rkp0bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:call-center-support-service-remix" /></template>
