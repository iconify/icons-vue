<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u43a0_poh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u43a0_poh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-right-up-16-solid" /></template>
