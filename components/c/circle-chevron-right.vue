<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5jz4bbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o5jz4bbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevron-right" /></template>
