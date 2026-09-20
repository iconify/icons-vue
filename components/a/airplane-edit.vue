<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peoz5pb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peoz5pb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-edit" /></template>
