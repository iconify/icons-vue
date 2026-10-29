<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsbk96brv.css';
import '../../css/o/odpdy0bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsbk96brv"/><path class="odpdy0bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:drag-handle" /></template>
