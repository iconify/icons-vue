<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x65w7rnui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x65w7rnui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:glider" /></template>
