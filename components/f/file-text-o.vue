<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd583-bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="qd583-bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-text-o" /></template>
