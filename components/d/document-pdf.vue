<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc8u2wqpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc8u2wqpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-pdf" /></template>
