<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/warw91tyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="warw91tyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mail-alarm-analog" /></template>
