<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccs_qsmmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccs_qsmmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-fill" /></template>
