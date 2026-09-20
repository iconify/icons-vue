<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sla9g7bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sla9g7bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:close-square-o" /></template>
