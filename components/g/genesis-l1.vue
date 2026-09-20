<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o23mbdcfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o23mbdcfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:genesis-l1" /></template>
