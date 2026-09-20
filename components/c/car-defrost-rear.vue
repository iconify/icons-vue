<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq1l64anc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq1l64anc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-defrost-rear" /></template>
