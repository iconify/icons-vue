<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs0u1_bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs0u1_bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:common-workflow-language" /></template>
