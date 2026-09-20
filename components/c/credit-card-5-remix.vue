<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-hvrfb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t-hvrfb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:credit-card-5-remix" /></template>
