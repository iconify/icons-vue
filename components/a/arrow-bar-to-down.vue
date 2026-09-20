<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khck6er_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khck6er_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-to-down" /></template>
