<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg_scyb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg_scyb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-fill" /></template>
