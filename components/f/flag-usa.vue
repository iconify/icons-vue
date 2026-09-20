<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq3i6bvzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iq3i6bvzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:flag-usa" /></template>
