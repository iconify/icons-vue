<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxlye1b8h.css';
import '../../css/o/o8elwl8sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dxlye1b8h"/><path class="o8elwl8sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-open-enterprise-languages" /></template>
