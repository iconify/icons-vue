<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l231--b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l231--b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:diagram-3-fill" /></template>
