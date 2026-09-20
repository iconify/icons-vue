<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcuuxbb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcuuxbb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-number-7-filled" /></template>
