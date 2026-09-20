<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs7opybrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs7opybrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-fill" /></template>
