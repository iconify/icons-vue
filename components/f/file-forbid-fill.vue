<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wec3zqpus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wec3zqpus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-forbid-fill" /></template>
