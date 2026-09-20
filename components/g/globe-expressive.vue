<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ythgtnbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ythgtnbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:globe-expressive" /></template>
