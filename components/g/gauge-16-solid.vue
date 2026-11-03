<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei6tb3pbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ei6tb3pbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gauge-16-solid" /></template>
