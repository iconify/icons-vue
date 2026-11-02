<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awcw3vb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awcw3vb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:desk-fill" /></template>
