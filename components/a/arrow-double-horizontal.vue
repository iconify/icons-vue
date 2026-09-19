<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agcbpgbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="agcbpgbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-double-horizontal" /></template>
