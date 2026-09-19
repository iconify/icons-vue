<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mimxhhbzg.css';
import '../../css/l/l12r2ccpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mimxhhbzg"/><path class="l12r2ccpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:copy-solid" /></template>
