<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmbkaq7lv.css';
import '../../css/p/pktx-jbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tmbkaq7lv"/><path class="pktx-jbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jetbrains" /></template>
