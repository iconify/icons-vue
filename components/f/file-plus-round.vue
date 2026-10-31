<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4_r_ib6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4_r_ib6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-plus-round" /></template>
