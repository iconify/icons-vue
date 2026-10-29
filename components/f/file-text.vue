<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlejs_b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlejs_b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-text" /></template>
