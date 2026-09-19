<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acnjw_bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acnjw_bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-hourglass" /></template>
