<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c93n78bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c93n78bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bear-fill-round" /></template>
