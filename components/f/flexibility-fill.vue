<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-2lwccod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-2lwccod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flexibility-fill" /></template>
