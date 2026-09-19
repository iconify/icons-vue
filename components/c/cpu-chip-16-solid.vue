<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqsh3o3jo.css';
import '../../css/e/e2-a4zbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iqsh3o3jo"/><path clip-rule="evenodd" class="e2-a4zbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cpu-chip-16-solid" /></template>
