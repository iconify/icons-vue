<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qry4i52_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qry4i52_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gauge-gloss" /></template>
