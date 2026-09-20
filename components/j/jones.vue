<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkmwa6k4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkmwa6k4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:jones" /></template>
