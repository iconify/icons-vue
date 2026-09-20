<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s80e3ct_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s80e3ct_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-2-line" /></template>
