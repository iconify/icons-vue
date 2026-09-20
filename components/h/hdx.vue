<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u576o3b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u576o3b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hdx" /></template>
