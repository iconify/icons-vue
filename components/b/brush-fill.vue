<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1w7a08jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g1w7a08jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brush-fill" /></template>
