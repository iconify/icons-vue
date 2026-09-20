<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w52tpizdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w52tpizdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-new-line" /></template>
