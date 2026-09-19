<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdldcwb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdldcwb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-graph-up-right" /></template>
