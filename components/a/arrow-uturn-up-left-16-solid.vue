<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-5hcsb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r-5hcsb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-up-left-16-solid" /></template>
