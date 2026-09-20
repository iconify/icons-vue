<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-cegabsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-cegabsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-justify-end" /></template>
