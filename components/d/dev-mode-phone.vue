<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/db-rwxb2n.css';
import '../../css/m/mcca7odma.css';
import '../../css/m/mc609bhih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="db-rwxb2n"/><path class="mcca7odma"/><path class="mc609bhih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:dev-mode-phone" /></template>
