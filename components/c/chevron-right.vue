<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk5u3zgrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wk5u3zgrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:chevron-right" /></template>
