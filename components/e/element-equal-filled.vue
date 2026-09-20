<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edvaug9pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edvaug9pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:element-equal-filled" /></template>
