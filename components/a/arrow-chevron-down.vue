<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t48mlfbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t48mlfbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-chevron-down" /></template>
