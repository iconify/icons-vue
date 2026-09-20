<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3k3cbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek3k3cbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:airplane" /></template>
