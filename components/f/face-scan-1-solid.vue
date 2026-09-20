<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vopa7kdbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vopa7kdbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:face-scan-1-solid" /></template>
