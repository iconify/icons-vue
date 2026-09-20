<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_lph5so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v3_lph5so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:family-practice" /></template>
