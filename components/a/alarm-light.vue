<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clh0w3bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clh0w3bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-light" /></template>
