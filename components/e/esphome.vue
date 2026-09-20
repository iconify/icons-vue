<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqs725hfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqs725hfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:esphome" /></template>
