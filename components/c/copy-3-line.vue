<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oip9e8p0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oip9e8p0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-3-line" /></template>
