<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lznn-3o3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lznn-3o3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:hairdresser" /></template>
