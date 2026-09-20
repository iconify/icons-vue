<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9wih73ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9wih73ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-60" /></template>
