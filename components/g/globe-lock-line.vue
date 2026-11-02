<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orkb68b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orkb68b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-lock-line" /></template>
