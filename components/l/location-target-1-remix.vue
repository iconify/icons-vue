<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo8u7cwpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yo8u7cwpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:location-target-1-remix" /></template>
