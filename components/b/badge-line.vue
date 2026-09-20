<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afpisrply.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afpisrply"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-line" /></template>
