<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8vghd45x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8vghd45x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-z-fill-round" /></template>
