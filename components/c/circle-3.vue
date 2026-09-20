<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auhlrw2_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="auhlrw2_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:circle-3" /></template>
