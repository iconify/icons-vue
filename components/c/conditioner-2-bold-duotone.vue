<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9_1xi4pr.css';
import '../../css/a/anh277ned.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9_1xi4pr"/><path class="anh277ned"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:conditioner-2-bold-duotone" /></template>
