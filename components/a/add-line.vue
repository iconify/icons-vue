<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm_3ngbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm_3ngbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-line" /></template>
