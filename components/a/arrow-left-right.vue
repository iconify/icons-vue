<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xct69xb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xct69xb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-left-right" /></template>
