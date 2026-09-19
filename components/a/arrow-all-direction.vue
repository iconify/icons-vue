<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g06rgycvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g06rgycvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-all-direction" /></template>
