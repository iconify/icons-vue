<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfi7w5aob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfi7w5aob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:amkt" /></template>
