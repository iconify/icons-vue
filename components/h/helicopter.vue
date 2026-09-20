<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afg6-l8sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afg6-l8sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:helicopter" /></template>
