<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/citlsybef.css';
import '../../css/k/kd8sdbbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="citlsybef"/><path class="kd8sdbbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fls" /></template>
