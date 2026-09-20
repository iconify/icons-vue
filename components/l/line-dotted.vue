<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp4j1ldlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="lp4j1ldlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:line-dotted" /></template>
