<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6hpmnb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6hpmnb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-matrix" /></template>
