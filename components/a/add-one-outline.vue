<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz4-e3b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oz4-e3b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:add-one-outline" /></template>
