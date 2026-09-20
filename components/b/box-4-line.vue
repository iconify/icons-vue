<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iun0xth8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iun0xth8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-4-line" /></template>
