<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpps7ovwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpps7ovwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:directions" /></template>
