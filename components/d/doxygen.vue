<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in43hzbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":438,"height":512};
const content = `<path class="in43hzbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:doxygen" /></template>
