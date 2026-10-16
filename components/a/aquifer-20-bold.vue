<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfnsa8bub.css';
import '../../css/u/u6s26w-eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rfnsa8bub"/><path class="u6s26w-eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aquifer-20-bold" /></template>
