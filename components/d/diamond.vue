<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4im9-bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g4im9-bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:diamond" /></template>
