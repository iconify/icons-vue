<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug-mjlbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ug-mjlbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:diagram-3" /></template>
