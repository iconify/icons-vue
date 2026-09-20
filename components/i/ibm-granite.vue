<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmmfejias.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmmfejias"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ibm-granite" /></template>
