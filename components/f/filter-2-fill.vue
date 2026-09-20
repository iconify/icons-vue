<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9g9lhbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f9g9lhbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-2-fill" /></template>
