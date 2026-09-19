<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnjr8vb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":32};
const content = `<path class="fnjr8vb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:beaker" /></template>
