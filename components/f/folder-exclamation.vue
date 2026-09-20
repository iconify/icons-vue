<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_dfwp-1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_dfwp-1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-exclamation" /></template>
