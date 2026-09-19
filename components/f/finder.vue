<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2x25mbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="u2x25mbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:finder" /></template>
