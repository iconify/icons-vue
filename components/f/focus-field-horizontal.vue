<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytz6a3bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytz6a3bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:focus-field-horizontal" /></template>
