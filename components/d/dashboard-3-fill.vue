<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2vd5wbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2vd5wbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-3-fill" /></template>
