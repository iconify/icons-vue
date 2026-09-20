<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2n2h6b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2n2h6b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-search-line" /></template>
