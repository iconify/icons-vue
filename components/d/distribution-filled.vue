<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5433x7qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i5433x7qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:distribution-filled" /></template>
