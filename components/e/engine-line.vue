<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9ywx-8pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9ywx-8pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:engine-line" /></template>
