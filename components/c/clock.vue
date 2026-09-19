<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebldvkbho.css';
import '../../css/r/r6mnptbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="r6mnptbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:clock" /></template>
