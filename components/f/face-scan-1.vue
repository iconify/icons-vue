<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scyo_vb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="scyo_vb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:face-scan-1" /></template>
