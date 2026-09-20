<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owc77-wfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owc77-wfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-right" /></template>
