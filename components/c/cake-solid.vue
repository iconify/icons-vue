<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4og4ecad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4og4ecad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cake-solid" /></template>
