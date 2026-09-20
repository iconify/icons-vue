<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxknr-n4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxknr-n4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:linkedin-fill" /></template>
