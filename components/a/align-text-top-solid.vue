<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzkkfsi5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qzkkfsi5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:align-text-top-solid" /></template>
