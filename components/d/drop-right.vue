<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p21ha7b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p21ha7b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:drop-right" /></template>
