<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtkgymbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtkgymbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-top" /></template>
