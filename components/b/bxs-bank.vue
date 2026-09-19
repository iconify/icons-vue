<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txy4c3lcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txy4c3lcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bank" /></template>
