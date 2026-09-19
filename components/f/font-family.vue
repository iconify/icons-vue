<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1a9pt74t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1a9pt74t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:font-family" /></template>
