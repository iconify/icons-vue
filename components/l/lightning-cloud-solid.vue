<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opoqdejcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="opoqdejcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:lightning-cloud-solid" /></template>
