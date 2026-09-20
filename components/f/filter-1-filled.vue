<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqur9absj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqur9absj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:filter-1-filled" /></template>
