<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq1u79b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq1u79b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-center-fill" /></template>
