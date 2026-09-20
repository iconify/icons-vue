<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd4yx7c9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd4yx7c9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-horizontal" /></template>
