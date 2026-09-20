<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfcmr664f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rfcmr664f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-tv-tower" /></template>
