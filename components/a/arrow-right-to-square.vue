<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdln7bb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qdln7bb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-right-to-square" /></template>
