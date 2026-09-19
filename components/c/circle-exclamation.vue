<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm4ww6bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jm4ww6bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-exclamation" /></template>
