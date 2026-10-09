<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chhb4kirx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chhb4kirx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bazarr" /></template>
