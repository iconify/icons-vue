<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbk-iydcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbk-iydcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:corner-down-left" /></template>
