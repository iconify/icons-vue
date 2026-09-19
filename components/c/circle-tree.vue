<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-2g7-zdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q-2g7-zdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-tree" /></template>
