<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sysu8gbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sysu8gbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevron-up" /></template>
