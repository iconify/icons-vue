<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5p4vbcgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x5p4vbcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-double-fill-16" /></template>
