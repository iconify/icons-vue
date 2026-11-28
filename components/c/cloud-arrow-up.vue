<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8tb2oehp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8tb2oehp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-arrow-up" /></template>
