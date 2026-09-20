<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl0kpm0-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl0kpm0-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-bold-circle" /></template>
