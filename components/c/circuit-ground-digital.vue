<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8d72bstt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8d72bstt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-ground-digital" /></template>
