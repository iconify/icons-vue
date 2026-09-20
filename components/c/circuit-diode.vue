<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c648gabjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c648gabjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-diode" /></template>
