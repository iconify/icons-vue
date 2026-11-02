<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plm5xnbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plm5xnbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-axis-3d-line" /></template>
