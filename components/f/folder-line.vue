<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8_w0s-7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8_w0s-7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-line" /></template>
