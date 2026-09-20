<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny9k_dr0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ny9k_dr0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:computer-outline" /></template>
