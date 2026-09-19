<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm4e9_79y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm4e9_79y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-up-arrow-circle" /></template>
