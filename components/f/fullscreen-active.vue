<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbmc7blgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tbmc7blgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:fullscreen-active" /></template>
