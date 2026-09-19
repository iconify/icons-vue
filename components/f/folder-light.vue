<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc7to4b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc7to4b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-light" /></template>
