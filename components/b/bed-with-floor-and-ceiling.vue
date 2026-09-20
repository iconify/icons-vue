<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr9hqtbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tr9hqtbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bed-with-floor-and-ceiling" /></template>
