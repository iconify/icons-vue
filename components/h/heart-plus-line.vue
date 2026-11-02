<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugnsamf_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugnsamf_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-plus-line" /></template>
