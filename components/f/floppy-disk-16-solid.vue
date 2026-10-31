<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3xgy8mzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x3xgy8mzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:floppy-disk-16-solid" /></template>
