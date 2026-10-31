<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wym4_cc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wym4_cc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:building-2-gloss" /></template>
