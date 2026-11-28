<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t51abbooa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t51abbooa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-list-x" /></template>
