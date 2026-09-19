<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q386gwb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q386gwb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-down-l" /></template>
