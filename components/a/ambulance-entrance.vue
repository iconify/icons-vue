<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnx8_rqso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnx8_rqso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:ambulance-entrance" /></template>
