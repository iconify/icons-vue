<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcc-cbb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jcc-cbb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:globe-central-south-asia-fill" /></template>
