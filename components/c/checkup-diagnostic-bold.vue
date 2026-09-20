<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgu-p0blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgu-p0blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:checkup-diagnostic-bold" /></template>
