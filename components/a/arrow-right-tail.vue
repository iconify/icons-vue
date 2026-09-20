<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7knmwi9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7knmwi9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right-tail" /></template>
