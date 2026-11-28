<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni3q_32ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni3q_32ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-pdf-solid" /></template>
