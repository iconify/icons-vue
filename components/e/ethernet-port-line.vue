<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie46jk5tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie46jk5tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ethernet-port-line" /></template>
