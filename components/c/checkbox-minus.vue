<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r07gb5b7z.css';
import '../../css/k/kev4430ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r07gb5b7z"/><path class="kev4430ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:checkbox-minus" /></template>
