<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpdpley1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpdpley1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:edge-computing-outlined" /></template>
