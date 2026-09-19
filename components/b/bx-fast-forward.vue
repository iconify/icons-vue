<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrtgdmbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrtgdmbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-fast-forward" /></template>
