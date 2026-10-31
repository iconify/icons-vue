<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvw8pmbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvw8pmbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fish-gloss" /></template>
