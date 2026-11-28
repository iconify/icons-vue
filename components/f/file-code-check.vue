<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl6cospbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl6cospbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-code-check" /></template>
