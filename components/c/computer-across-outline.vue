<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcqxiub3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vcqxiub3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:computer-across-outline" /></template>
