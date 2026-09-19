<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idnx1mbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="idnx1mbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-invoice" /></template>
