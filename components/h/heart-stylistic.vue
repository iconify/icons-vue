<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt2lyl8rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt2lyl8rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:heart-stylistic" /></template>
