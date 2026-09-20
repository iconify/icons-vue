<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybu4mabje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybu4mabje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dwavesystems" /></template>
