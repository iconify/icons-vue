<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pct8yx7mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pct8yx7mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-refresh" /></template>
