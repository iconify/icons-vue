<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz6-anbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz6-anbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-2-line" /></template>
