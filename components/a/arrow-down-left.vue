<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgoo95b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rgoo95b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-down-left" /></template>
