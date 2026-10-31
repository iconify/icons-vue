<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr1mw-09t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr1mw-09t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-1-fill-round" /></template>
