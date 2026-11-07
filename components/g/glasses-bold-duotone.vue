<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fudxizbvs.css';
import '../../css/x/x0_riwbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fudxizbvs"/><path class="x0_riwbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:glasses-bold-duotone" /></template>
