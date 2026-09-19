<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5bqxjb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5bqxjb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chevron-left-square" /></template>
