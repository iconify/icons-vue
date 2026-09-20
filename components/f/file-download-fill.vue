<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtkl9p4jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtkl9p4jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-download-fill" /></template>
