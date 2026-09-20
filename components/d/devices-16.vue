<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7degyn_m.css';
import '../../css/w/wt6yq6kuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v7degyn_m"/><path class="wt6yq6kuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:devices-16" /></template>
