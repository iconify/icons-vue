<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdo1a8bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdo1a8bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-powerpoint" /></template>
