<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frg06o3hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="frg06o3hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-left-to-line" /></template>
