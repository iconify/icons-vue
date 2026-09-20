<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9-2tcckm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r9-2tcckm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:computer-laptop-16-solid" /></template>
