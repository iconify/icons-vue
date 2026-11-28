<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzec2b5dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzec2b5dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-check" /></template>
