<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkzro1tab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bkzro1tab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:diploma" /></template>
