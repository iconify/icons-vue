<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob03obcjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob03obcjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-gunnarp-panel" /></template>
