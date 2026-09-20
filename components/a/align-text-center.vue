<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh59gvbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh59gvbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:align-text-center" /></template>
