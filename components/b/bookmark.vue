<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioh0fbcui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioh0fbcui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bookmark" /></template>
