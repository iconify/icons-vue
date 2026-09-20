<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyrw1ub6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lyrw1ub6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrows-crossing-16-solid" /></template>
