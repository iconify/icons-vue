<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miq8s0bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miq8s0bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-json-solid" /></template>
