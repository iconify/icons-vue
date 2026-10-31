<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj4xylkqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj4xylkqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-small-bulk-round" /></template>
