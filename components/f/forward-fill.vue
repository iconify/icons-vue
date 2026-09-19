<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiz4bsboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oiz4bsboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:forward-fill" /></template>
