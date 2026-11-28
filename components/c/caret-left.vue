<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3v303tmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3v303tmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:caret-left" /></template>
