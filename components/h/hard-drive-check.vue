<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2nvtzvxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2nvtzvxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hard-drive-check" /></template>
