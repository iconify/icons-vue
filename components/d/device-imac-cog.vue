<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awzzv57ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awzzv57ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-cog" /></template>
