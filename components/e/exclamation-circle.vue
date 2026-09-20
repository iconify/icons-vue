<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1e3frofp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1e3frofp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:exclamation-circle" /></template>
