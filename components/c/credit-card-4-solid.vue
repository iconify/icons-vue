<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_-c-qonv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q_-c-qonv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:credit-card-4-solid" /></template>
