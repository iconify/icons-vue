<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on9-4bc_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on9-4bc_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-refresh" /></template>
