<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okti615sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okti615sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:handle-bottom-right" /></template>
