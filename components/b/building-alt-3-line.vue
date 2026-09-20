<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmhlr2brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmhlr2brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:building-alt-3-line" /></template>
