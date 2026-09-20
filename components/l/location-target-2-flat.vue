<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr8b3abzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nr8b3abzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:location-target-2-flat" /></template>
