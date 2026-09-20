<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9vpst2pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9vpst2pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-ai" /></template>
