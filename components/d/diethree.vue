<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd_y6vbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":959};
const content = `<path class="rd_y6vbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:diethree" /></template>
