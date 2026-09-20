<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht007_bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ht007_bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:fireplace" /></template>
