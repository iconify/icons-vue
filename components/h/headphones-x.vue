<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klgc4_9wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klgc4_9wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:headphones-x" /></template>
