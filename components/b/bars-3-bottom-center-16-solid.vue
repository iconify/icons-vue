<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_4k9-uiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c_4k9-uiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bars-3-bottom-center-16-solid" /></template>
