<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqmi1bi_j.css';
import '../../css/i/i9il0nflb.css';
import '../../css/i/ijudkumzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wqmi1bi_j"/><path class="i9il0nflb"/><path class="ijudkumzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:kdl" /></template>
