<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmkebn1_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmkebn1_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-code-line" /></template>
