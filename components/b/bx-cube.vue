<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvq1561eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvq1561eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cube" /></template>
