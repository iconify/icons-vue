<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ywehbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e2ywehbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:hammer-16-solid" /></template>
