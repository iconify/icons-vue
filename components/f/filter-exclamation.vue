<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3jpf0bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3jpf0bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-exclamation" /></template>
