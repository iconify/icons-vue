<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgib-pbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qgib-pbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:christian-cross-2" /></template>
