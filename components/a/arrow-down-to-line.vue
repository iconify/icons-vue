<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_tgjwbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x_tgjwbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-down-to-line" /></template>
