<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy0ljfbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yy0ljfbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:lightning-charge-fill" /></template>
