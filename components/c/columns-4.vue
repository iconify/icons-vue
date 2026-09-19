<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6_06_per.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6_06_per"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:columns-4" /></template>
