<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmksrn_vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmksrn_vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-check-fill" /></template>
