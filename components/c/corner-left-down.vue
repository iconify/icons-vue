<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxva56-py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxva56-py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:corner-left-down" /></template>
