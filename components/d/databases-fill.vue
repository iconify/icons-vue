<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh6ubd6eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nh6ubd6eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:databases-fill" /></template>
