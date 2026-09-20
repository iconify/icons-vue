<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nolju0brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nolju0brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-dashed" /></template>
