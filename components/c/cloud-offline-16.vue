<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jky5v_bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jky5v_bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cloud-offline-16" /></template>
