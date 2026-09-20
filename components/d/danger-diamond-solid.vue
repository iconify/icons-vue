<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q938jdcxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q938jdcxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:danger-diamond-solid" /></template>
