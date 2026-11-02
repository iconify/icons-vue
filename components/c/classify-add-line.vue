<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re234w22x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re234w22x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-add-line" /></template>
