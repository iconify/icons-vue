<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p141vldzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p141vldzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lucky-coin-solid" /></template>
