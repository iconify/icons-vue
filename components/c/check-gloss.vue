<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh1qoo5sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh1qoo5sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-gloss" /></template>
