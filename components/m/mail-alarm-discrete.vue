<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yncsv2wwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yncsv2wwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mail-alarm-discrete" /></template>
