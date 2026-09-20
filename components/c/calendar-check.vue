<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp687xbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp687xbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-check" /></template>
