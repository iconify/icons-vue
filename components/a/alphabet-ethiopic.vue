<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwnx8bzkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwnx8bzkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alphabet-ethiopic" /></template>
