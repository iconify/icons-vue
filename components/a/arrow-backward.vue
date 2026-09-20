<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjrbmybqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rjrbmybqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:arrow-backward" /></template>
