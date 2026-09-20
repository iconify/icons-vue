<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry0j3ldww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry0j3ldww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:doc-fill" /></template>
