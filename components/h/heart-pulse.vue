<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqbhmpblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqbhmpblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:heart-pulse" /></template>
