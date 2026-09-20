<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1c-5hbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1c-5hbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:angle-right" /></template>
