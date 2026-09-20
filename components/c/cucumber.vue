<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ev_2b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ev_2b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cucumber" /></template>
