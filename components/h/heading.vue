<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkwr-26dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wkwr-26dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:heading" /></template>
