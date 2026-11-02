<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf2iqfbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf2iqfbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-distribute-center-line" /></template>
