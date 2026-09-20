<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0yuccxjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p0yuccxjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alarm-sleep-filled" /></template>
