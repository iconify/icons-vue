<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz4k-cbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz4k-cbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-2-line" /></template>
