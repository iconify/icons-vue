<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/org_560qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="org_560qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-word-fill" /></template>
