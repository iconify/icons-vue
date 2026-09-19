<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/few9-1b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="few9-1b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ear" /></template>
