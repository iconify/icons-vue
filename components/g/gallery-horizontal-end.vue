<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjigr4ppa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjigr4ppa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-horizontal-end" /></template>
