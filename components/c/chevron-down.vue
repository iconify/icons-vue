<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyd2g7b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jyd2g7b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:chevron-down" /></template>
