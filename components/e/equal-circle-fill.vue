<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qirr8n72d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qirr8n72d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:equal-circle-fill" /></template>
