<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjvaacb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rjvaacb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:lightning" /></template>
