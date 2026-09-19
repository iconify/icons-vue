<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxeb_qbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxeb_qbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:creality-complete" /></template>
