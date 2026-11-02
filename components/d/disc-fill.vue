<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwuv_ubtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwuv_ubtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disc-fill" /></template>
