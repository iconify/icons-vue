<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz261zbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gz261zbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-left-2-fill" /></template>
