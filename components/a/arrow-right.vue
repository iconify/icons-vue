<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv5qt_s0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="qv5qt_s0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:arrow-right" /></template>
