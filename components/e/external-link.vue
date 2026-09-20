<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da27cu_vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da27cu_vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:external-link" /></template>
