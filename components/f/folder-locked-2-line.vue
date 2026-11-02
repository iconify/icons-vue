<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjirbivsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjirbivsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-locked-2-line" /></template>
