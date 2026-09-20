<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6qm1-1vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6qm1-1vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-share" /></template>
