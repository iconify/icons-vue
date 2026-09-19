<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utdc-ibes.css';
import '../../css/e/ebr8uinkx.css';
import '../../css/i/ibwikzbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="utdc-ibes"/><circle class="ebr8uinkx"/><circle class="ibwikzbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:just" /></template>
