<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz03p4bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iz03p4bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:hardclipcurve" /></template>
