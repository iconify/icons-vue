<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ure9msbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ure9msbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-center-solid" /></template>
