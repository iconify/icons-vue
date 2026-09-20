<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5pp66bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5pp66bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anchor-line" /></template>
