<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2nnhybxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q2nnhybxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:camera-1-solid" /></template>
