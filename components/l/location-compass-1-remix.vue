<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6p4lbbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h6p4lbbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:location-compass-1-remix" /></template>
