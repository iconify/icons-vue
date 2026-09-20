<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq1r-no-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mq1r-no-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:hopscotch" /></template>
