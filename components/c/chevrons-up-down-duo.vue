<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_sdfkb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_sdfkb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-up-down-duo" /></template>
