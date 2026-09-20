<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujm9vhbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ujm9vhbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-vertical-stipple" /></template>
