<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyi5vz6mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyi5vz6mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-up-line" /></template>
