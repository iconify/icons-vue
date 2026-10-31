<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmqw5xbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmqw5xbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:car-gloss" /></template>
