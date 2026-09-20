<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb2g502qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb2g502qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-right-solid" /></template>
