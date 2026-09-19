<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezkmt2vox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ezkmt2vox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cast-connected" /></template>
