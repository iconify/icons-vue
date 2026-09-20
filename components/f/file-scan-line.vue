<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esb7-8xxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esb7-8xxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-scan-line" /></template>
