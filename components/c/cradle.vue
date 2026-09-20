<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhgit_tcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhgit_tcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cradle" /></template>
