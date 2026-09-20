<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rram23-dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rram23-dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-add" /></template>
