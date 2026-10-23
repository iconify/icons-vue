<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-1v2wi4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1v2wi4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grid-2x2-plus" /></template>
