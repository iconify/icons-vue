<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9qjobbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k9qjobbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chart-line-up-16-solid" /></template>
